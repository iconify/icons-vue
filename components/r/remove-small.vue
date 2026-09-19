<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxt91fbdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="uxt91fbdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:remove-small" /></template>
