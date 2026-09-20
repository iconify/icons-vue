<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t805-accq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t805-accq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mailchimp" /></template>
