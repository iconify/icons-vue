<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etjlzh90r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="etjlzh90r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:tool" /></template>
