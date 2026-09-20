<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjfl4gbzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjfl4gbzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:phone-callback-line" /></template>
