<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie3zn7bfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ie3zn7bfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:map-pin-slash-solid" /></template>
