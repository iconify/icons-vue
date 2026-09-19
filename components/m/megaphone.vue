<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4hs4hvwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":520,"height":464};
const content = `<path class="w4hs4hvwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:megaphone" /></template>
