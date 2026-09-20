<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_mu3rdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="v3_mu3rdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:note-outline" /></template>
