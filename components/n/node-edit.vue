<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/f/f90d6rh1v.css';
import '../../css/g/g-i8fs05n.css';
import '../../css/k/kv6qicbin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="f90d6rh1v"/><path class="g-i8fs05n"/><path class="kv6qicbin"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:node-edit" /></template>
