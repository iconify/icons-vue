<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idn_oykcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="idn_oykcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:namuwiki" /></template>
