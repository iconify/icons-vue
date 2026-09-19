<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbi1n57ce.css';
import '../../css/g/gwi370brj.css';
import '../../css/l/lblj8jhet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bbi1n57ce"/><path class="gwi370brj"/><path class="lblj8jhet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:volume-mute" /></template>
