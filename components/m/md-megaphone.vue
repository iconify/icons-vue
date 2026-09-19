<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sg1osvr1r.css';
import '../../css/p/pgf0clsgf.css';
import '../../css/s/s0rj7obem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sg1osvr1r"/><path class="pgf0clsgf"/><path class="s0rj7obem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-megaphone" /></template>
