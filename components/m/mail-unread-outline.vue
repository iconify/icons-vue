<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ug7viwfag.css';
import '../../css/a/atf7rkfzt.css';
import '../../css/s/sntxj5r0a.css';
import '../../css/b/bvllc8w-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ug7viwfag"/><path class="atf7rkfzt"/><circle class="sntxj5r0a"/><path class="bvllc8w-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:mail-unread-outline" /></template>
