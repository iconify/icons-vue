<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rc08kibud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rc08kibud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:text-align-right" /></template>
