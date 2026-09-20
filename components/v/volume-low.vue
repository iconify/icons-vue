<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wu88th.css';
import '../../css/s/so-from-34.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wu88th"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:volume-low" /></template>
