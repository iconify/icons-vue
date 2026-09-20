<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/suv_jd7bc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="suv_jd7bc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:readarr-light" /></template>
