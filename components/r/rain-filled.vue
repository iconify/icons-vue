<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o37b6zcle.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o37b6zcle"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:rain-filled" /></template>
