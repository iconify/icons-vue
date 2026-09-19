<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wty6jmb4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wty6jmb4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:telescope" /></template>
