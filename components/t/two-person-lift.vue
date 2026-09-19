<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icsbmobje.css';
import '../../css/b/bweidcb3i.css';
import '../../css/f/fktdbrb-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="icsbmobje"/><path class="bweidcb3i"/><path class="fktdbrb-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:two-person-lift" /></template>
