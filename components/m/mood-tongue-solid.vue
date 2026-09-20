<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfvpij5gy.css';
import '../../css/j/jdy0pvxyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dfvpij5gy"/><path clip-rule="evenodd" class="jdy0pvxyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:mood-tongue-solid" /></template>
