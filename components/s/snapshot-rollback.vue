<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcus66bon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bcus66bon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:snapshot-rollback" /></template>
