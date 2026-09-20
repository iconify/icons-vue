<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da9f7744f.css';
import '../../css/s/sj5wtjbpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="da9f7744f"/><path class="sj5wtjbpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:repo-delete-24" /></template>
