<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ty51eibwy.css';
import '../../css/x/xi_khzqzd.css';
import '../../css/b/beok1wbax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ty51eibwy"/><path class="xi_khzqzd"/><path class="beok1wbax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:mic-off-outline" /></template>
