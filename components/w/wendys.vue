<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/le0cgmbgy.css';
import '../../css/s/swqxefodk.css';
import '../../css/c/ci0zejzuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1230,"height":526};
const content = `<path class="le0cgmbgy"/><path class="swqxefodk"/><path class="ci0zejzuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:wendys" /></template>
