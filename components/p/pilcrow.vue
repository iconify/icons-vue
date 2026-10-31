<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sel7y4boo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sel7y4boo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:pilcrow" /></template>
