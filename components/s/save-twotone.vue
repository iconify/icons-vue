<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udhx9jb5f.css';
import '../../css/v/vzilmrbae.css';
import '../../css/u/um7ec_bhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="udhx9jb5f"/><path class="vzilmrbae"/><path class="um7ec_bhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:save-twotone" /></template>
