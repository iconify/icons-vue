<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adj7ecb1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="adj7ecb1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:timer-ten" /></template>
