<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f99tpmb6q.css';
import '../../css/q/qamjhebaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f99tpmb6q"/><path class="qamjhebaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:user-plus-duotone" /></template>
