<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9c993b2t.css';
import '../../css/y/yu6hplrgd.css';
import '../../css/k/kauhwtbid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x9c993b2t"/><path class="yu6hplrgd"/><path class="kauhwtbid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:washing-machine-48-bold" /></template>
