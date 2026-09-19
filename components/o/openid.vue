<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw5hcaclv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":472};
const content = `<path class="qw5hcaclv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:openid" /></template>
