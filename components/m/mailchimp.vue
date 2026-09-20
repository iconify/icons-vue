<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/va0w3o0-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="va0w3o0-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:mailchimp" /></template>
