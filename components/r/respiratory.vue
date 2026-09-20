<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grjwqbcjo.css';
import '../../css/t/tbbjvyiok.css';
import '../../css/u/ux3ufdb1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="grjwqbcjo"/><path class="tbbjvyiok"/><path class="ux3ufdb1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:respiratory" /></template>
