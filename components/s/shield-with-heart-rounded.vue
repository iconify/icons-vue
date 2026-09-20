<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixohtzbxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shield-with-heart-rounded" /></template>
<style>
.ixohtzbxn {
  fill: currentColor;
  d: path("M8.75 11.17q0 1.13 1.125 2.165q1.125 1.034 1.858 1.73q.13.106.27.106t.265-.102q.751-.675 1.866-1.728t1.116-2.172q0-.727-.53-1.252q-.531-.525-1.266-.525q-.448 0-.833.172t-.621.474q-.242-.303-.626-.474q-.383-.172-.828-.172q-.727 0-1.261.525q-.535.525-.535 1.252m2.964 9.648q-.15-.025-.282-.075q-2.951-1.125-4.691-3.816Q5 14.235 5 11.1V6.817q0-.514.293-.926q.292-.412.757-.597l5.385-2q.292-.106.565-.106t.566.106l5.384 2q.464.186.757.597q.293.412.293.926V11.1q0 3.135-1.74 5.826t-4.692 3.816q-.131.05-.281.075t-.287.025t-.287-.025");
}

</style>
