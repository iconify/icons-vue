<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkcf_lkax.css';
import '../../css/b/b98f6w00t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jkcf_lkax"/><path clip-rule="evenodd" class="b98f6w00t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:tv-16-solid" /></template>
