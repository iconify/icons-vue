<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6e9c4ivo.css';
import '../../css/s/s264hrbbe.css';
import '../../css/m/m5n_ehoon.css';
import '../../css/k/kemfy5bie.css';
import '../../css/d/d9s5sfbtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j6e9c4ivo"/><path clip-rule="evenodd" class="s264hrbbe"/><path class="m5n_ehoon"/><path clip-rule="evenodd" class="kemfy5bie"/><path class="d9s5sfbtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:search-results-duotone" /></template>
