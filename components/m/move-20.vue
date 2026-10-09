<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz03g9rra.css';
import '../../css/k/kz2zzrs0w.css';
import '../../css/a/a_pbj0bst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pz03g9rra"/><path class="kz2zzrs0w"/><path class="a_pbj0bst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:move-20" /></template>
