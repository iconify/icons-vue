<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w68_0ht6n.css';
import '../../css/m/mdqb7jbma.css';
import '../../css/c/cokcupbqs.css';
import '../../css/b/bvw1i0e9n.css';
import '../../css/c/c5-k5wbfw.css';
import '../../css/c/c256cbcmc.css';
import '../../css/y/y45uacjkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path clip-rule="evenodd" class="w68_0ht6n"/><path clip-rule="evenodd" class="mdqb7jbma"/><path class="cokcupbqs"/><circle class="bvw1i0e9n"/><path class="c5-k5wbfw"/><path class="c256cbcmc"/><path clip-rule="evenodd" class="y45uacjkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-ui:search" /></template>
