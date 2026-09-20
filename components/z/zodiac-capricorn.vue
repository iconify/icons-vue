<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmbhbh3kr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmbhbh3kr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:zodiac-capricorn" /></template>
