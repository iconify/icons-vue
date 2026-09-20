<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqy36eb7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqy36eb7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:microsoftexchange" /></template>
