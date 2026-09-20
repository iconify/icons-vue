<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/za2oecbdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="za2oecbdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yabin-dark" /></template>
