<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkw1mrb_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dkw1mrb_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:megaphone-24" /></template>
