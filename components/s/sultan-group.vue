<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmlvqk5-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tmlvqk5-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:sultan-group" /></template>
