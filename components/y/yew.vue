<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4sas9kjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4sas9kjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:yew" /></template>
