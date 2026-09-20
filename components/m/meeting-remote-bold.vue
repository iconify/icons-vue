<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ax4al5w4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ax4al5w4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:meeting-remote-bold" /></template>
