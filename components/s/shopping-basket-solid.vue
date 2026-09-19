<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bh9t6fjqh.css';
import '../../css/g/g_wd5geuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bh9t6fjqh"/><path clip-rule="evenodd" class="g_wd5geuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:shopping-basket-solid" /></template>
