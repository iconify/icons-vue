<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skrh6_4wv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="skrh6_4wv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:mantle" /></template>
