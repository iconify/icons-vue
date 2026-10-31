<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrscgzb-f.css';
import '../../css/s/st6uysbjd.css';
import '../../css/a/a-wwm5bze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="wrscgzb-f"/><path class="st6uysbjd"/><path class="a-wwm5bze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:north-korea" /></template>
