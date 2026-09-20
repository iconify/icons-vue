<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo_dqemwo.css';
import '../../css/r/r-kz3ibtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mo_dqemwo"/><path class="r-kz3ibtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:search-box-duotone" /></template>
