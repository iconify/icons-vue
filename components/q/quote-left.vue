<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahldpgp5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":34,"height":24};
const content = `<path class="ahldpgp5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:quote-left" /></template>
