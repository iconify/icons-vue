<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lu-e_c3za.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lu-e_c3za"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mailchimp-light" /></template>
