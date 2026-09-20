<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7orre6ne.css';
import '../../css/n/nk_c-zevr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x7orre6ne"/><path class="nk_c-zevr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:times-circle" /></template>
