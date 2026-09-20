<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ww0w2tjgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ww0w2tjgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:phone-check-filled" /></template>
