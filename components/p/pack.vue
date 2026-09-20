<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2ucobmfu.css';
import '../../css/z/z6ggt6ojm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k2ucobmfu"/><path class="z6ggt6ojm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:pack" /></template>
