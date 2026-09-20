<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwzhq8ujm.css';
import '../../css/m/mdm2icu2v.css';
import '../../css/o/oc6ekbbrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bwzhq8ujm"/><path clip-rule="evenodd" class="mdm2icu2v"/><path class="oc6ekbbrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:sort-alpha-desc-16" /></template>
