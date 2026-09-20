<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7owqu6zk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7owqu6zk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:personal-information-filled" /></template>
