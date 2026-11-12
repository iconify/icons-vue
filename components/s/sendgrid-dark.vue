<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6wtytb_v.css';
import '../../css/p/phf4gf3fs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i6wtytb_v"/><path class="phf4gf3fs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sendgrid-dark" /></template>
