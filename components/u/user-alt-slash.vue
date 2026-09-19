<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmc71fzqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="bmc71fzqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:user-alt-slash" /></template>
