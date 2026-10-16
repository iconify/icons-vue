<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2zpr60_w.css';
import '../../css/t/tx4fhibgn.css';
import '../../css/f/fj4vt1kml.css';
import '../../css/v/v2zc7vb1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s2zpr60_w"/><path class="tx4fhibgn"/><path class="fj4vt1kml"/><path class="v2zc7vb1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shovel-48" /></template>
