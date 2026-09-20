<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1xy5i58a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v1xy5i58a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:zerotier-light" /></template>
