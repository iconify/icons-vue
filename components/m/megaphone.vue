<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yi8tt5b8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yi8tt5b8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:megaphone" /></template>
