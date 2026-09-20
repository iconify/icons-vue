<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/augn52bzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="augn52bzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:phone-sharp-fill" /></template>
