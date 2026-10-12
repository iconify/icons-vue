<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrjmnmpml.css';
import '../../css/b/b595ytj-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rrjmnmpml"/><path class="b595ytj-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:phone-pause-stroke-20" /></template>
