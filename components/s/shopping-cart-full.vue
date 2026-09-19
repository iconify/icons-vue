<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0-a0abty.css';
import '../../css/v/v8sj7cvzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="b0-a0abty"/><path class="v8sj7cvzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:shopping-cart-full" /></template>
