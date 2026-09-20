<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp4uul4lk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="bp4uul4lk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:tennis" /></template>
