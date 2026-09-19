<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8dmqzbdr.css';
import '../../css/g/ge7idsbtu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="b8dmqzbdr"/><path class="ge7idsbtu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:notification-twotone" /></template>
