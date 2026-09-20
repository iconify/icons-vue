<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r86igdcpy.css';
import '../../css/z/zqwnycjqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r86igdcpy"/><path clip-rule="evenodd" class="zqwnycjqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:user-24" /></template>
