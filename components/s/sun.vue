<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtowsomii.css';
import '../../css/z/z3mr_0bdb.css';
import '../../css/y/y4ud7h78k.css';
import '../../css/g/ghnrqje-t.css';
import '../../css/h/ht860ybqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g class="jtowsomii"><path class="z3mr_0bdb"/><g transform="translate(-210 -1)"><path class="y4ud7h78k"/><circle class="ghnrqje-t"/><path class="ht860ybqd"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:sun" /></template>
