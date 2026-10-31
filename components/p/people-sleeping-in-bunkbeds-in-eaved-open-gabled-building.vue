<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t769otr5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t769otr5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:people-sleeping-in-bunkbeds-in-eaved-open-gabled-building" /></template>
