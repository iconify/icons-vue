<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skjyq2bzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="skjyq2bzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:umbrella-closed-variant" /></template>
