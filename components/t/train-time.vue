<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wd_kcpkgg.css';
import '../../css/j/j7n6imbex.css';
import '../../css/a/ar36zcbgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wd_kcpkgg"/><path class="j7n6imbex"/><path class="ar36zcbgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:train-time" /></template>
