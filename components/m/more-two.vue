<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/arj7difgh.css';
import '../../css/k/khw3qvnyj.css';
import '../../css/d/dami94nrg.css';
import '../../css/i/if0shbbto.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGqjEaheXL"><g class="ft5dv1b6b"><path class="arj7difgh"/><circle class="khw3qvnyj"/><circle class="dami94nrg"/><circle class="if0shbbto"/></g></mask></defs><path mask="url(#SVGqjEaheXL)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:more-two" /></template>
