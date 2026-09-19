<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5e7-8b-p.css';
import '../../css/q/qrtxhqwfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b5e7-8b-p"/><path class="qrtxhqwfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:user-account" /></template>
