<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmcdlcbwt.css';
import '../../css/j/jyt8hmbvk.css';
import '../../css/g/g57wd6_qr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lmcdlcbwt"/><path class="jyt8hmbvk"/><path class="g57wd6_qr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:mug-bold" /></template>
