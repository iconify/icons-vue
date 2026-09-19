<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/np-7czb9e.css';
import '../../css/n/nk4fjxbrm.css';
import '../../css/c/cz0muqbyq.css';
import '../../css/l/lxgl7abwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="np-7czb9e"/><path class="nk4fjxbrm"/><path class="cz0muqbyq"/><path class="lxgl7abwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:woocommerce-wordmark" /></template>
