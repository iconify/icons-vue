<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvvegsvlw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvvegsvlw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:topology-star-ring" /></template>
