<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ea-644bal.css';
import '../../css/i/iwz5x-bvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="ea-644bal"/><path class="iwz5x-bvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:pool-solid" /></template>
