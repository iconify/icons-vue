<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffpdv241p.css';
import '../../css/g/gk_jpucvn.css';
import '../../css/a/ayh926r5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ffpdv241p"/><path class="gk_jpucvn"/><path class="ayh926r5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tag-price-bold-duotone" /></template>
