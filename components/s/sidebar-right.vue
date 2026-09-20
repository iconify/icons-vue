<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqbnd2bxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gqbnd2bxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:sidebar-right" /></template>
