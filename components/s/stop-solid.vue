<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9qxd8bbn.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<rect class="clr-i-solid clr-i-solid-path-1 l9qxd8bbn"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:stop-solid" /></template>
