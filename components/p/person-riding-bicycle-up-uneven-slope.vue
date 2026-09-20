<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bu0j24bnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bu0j24bnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-riding-bicycle-up-uneven-slope" /></template>
