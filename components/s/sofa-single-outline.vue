<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2kb-5rgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2kb-5rgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sofa-single-outline" /></template>
