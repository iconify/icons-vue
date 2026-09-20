<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lb61gly2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lb61gly2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:shopping-bag-with-euro" /></template>
