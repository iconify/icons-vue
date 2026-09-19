<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhzvabbex.css';
import '../../css/q/q3_qw6b8e.css';
import '../../css/s/sdj60ogwn.css';
import '../../css/w/w76jl489n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rhzvabbex"/><path class="q3_qw6b8e"/><path class="sdj60ogwn"/><path class="w76jl489n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:new-dianziqian" /></template>
