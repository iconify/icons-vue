<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pf8jfjdus.css';
import '../../css/l/ltdti70ft.css';
import '../../css/r/rxr9zbc9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pf8jfjdus"/><path class="ltdti70ft"/><path class="rxr9zbc9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:shopping-shipping-shop" /></template>
