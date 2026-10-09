<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1middb0q.css';
import '../../css/b/b_86fhc7i.css';
import '../../css/n/nwv555bhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l1middb0q"/><path class="b_86fhc7i"/><path class="nwv555bhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:washing-machine-20" /></template>
