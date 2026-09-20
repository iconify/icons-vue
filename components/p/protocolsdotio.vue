<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8i2vpa4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j8i2vpa4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:protocolsdotio" /></template>
