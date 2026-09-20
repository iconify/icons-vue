<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjc0mib_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pjc0mib_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:versity-dark" /></template>
