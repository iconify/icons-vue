<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqg43f7sp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lqg43f7sp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:sad-tear-solid" /></template>
