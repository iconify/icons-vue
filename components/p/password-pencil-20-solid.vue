<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqof0hp_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="dqof0hp_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:password-pencil-20-solid" /></template>
