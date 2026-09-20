<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-ju2fxdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-ju2fxdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:more-horiz-line" /></template>
