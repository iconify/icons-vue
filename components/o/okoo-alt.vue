<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9ptq3a0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9ptq3a0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:okoo-alt" /></template>
