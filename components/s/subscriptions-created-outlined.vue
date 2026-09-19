<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-dvcfb3w.css';
import '../../css/f/fcilczb-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-dvcfb3w"/><path class="fcilczb-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:subscriptions-created-outlined" /></template>
