<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfr2iof0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfr2iof0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:pinwheel" /></template>
