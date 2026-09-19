<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8zjprbue.css';
import '../../css/o/o9cqsdb8n.css';
import '../../css/r/rua3i3zlo.css';
import '../../css/w/w44oc6c8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="m8zjprbue"/><path class="o9cqsdb8n"/><path class="rua3i3zlo"/><path class="w44oc6c8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:skull" /></template>
