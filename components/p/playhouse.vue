<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bebc3s2zk.css';
import '../../css/w/whljx5b0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bebc3s2zk"/><path class="whljx5b0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:playhouse" /></template>
