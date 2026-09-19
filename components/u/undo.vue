<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zk-762bui.css';
import '../../css/x/xi6rm2m0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="zk-762bui"/><path class="xi6rm2m0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:undo" /></template>
