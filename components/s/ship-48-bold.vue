<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbfaewbaw.css';
import '../../css/s/scknzcbae.css';
import '../../css/d/d672b0b5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jbfaewbaw"/><path class="scknzcbae"/><path class="d672b0b5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ship-48-bold" /></template>
