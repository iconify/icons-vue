<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ni_8jsb-d.css';
import '../../css/t/tblwxac3r.css';
import '../../css/b/bkf_frbkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<rect class="ni_8jsb-d"/><rect class="tblwxac3r"/><path class="bkf_frbkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:typer" /></template>
