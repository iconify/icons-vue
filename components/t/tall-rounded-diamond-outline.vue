<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_mhozbka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="v_mhozbka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tall-rounded-diamond-outline" /></template>
