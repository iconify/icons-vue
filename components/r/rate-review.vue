<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ar_sh6b-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":408,"height":432};
const content = `<path class="ar_sh6b-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:rate-review" /></template>
