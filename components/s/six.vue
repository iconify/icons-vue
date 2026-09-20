<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fs770bsej.css';
import '../../css/z/ztyr4ccyb.css';
import '../../css/q/q8nk54bpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fs770bsej"/><path class="ztyr4ccyb"/><path class="q8nk54bpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:six" /></template>
