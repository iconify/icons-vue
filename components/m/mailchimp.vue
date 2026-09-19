<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzmadub0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="rzmadub0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:mailchimp" /></template>
