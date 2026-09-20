<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekzz-41rw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ekzz-41rw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mydrive-dark" /></template>
