<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-2li_llf.css';
import '../../css/n/n9o42e7zi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j-2li_llf"/><path class="n9o42e7zi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:sort-amount-asc" /></template>
