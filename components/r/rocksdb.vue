<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pol6cgbck.css';
import '../../css/d/drobpt_me.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="pol6cgbck"/><path class="drobpt_me"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:rocksdb" /></template>
