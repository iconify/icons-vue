<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/luyo9rbub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="luyo9rbub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mailchimp-dark" /></template>
