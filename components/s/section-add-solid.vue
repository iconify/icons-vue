<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xheqzs9ut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="xheqzs9ut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:section-add-solid" /></template>
