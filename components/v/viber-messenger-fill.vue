<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9--6g2ow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j9--6g2ow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:viber-messenger-fill" /></template>
