<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcq57kfry.css';
import '../../css/b/b26cuwy7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wcq57kfry"/><path class="b26cuwy7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:phone-twotone" /></template>
