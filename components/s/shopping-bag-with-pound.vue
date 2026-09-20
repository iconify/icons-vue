<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ril3z_bku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ril3z_bku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:shopping-bag-with-pound" /></template>
