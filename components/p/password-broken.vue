<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="cpqoopb6x"/><path class="ucmhfwbcn"/><path class="kom0ajijq"/><path class="spvw1m4wo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:password-broken" /></template>
<style>
.cpqoopb6x {
  d: path("M12.0002 10V11.9997M12.0002 11.9997V12.0002M12.0002 11.9997L13.7317 11M12.0002 11.9997L11.9997 11.9999M12.0002 12.0002V14M12.0002 12.0002L11.9997 11.9999M12.0002 12.0002L13.7319 13M10.2678 11L11.9997 11.9999M11.9997 11.9999L10.2676 13");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kom0ajijq {
  d: path("M17.2686 10V11.9997M17.2686 11.9997V12.0002M17.2686 11.9997L19 11M17.2686 11.9997L17.2681 11.9999M17.2686 12.0002V14M17.2686 12.0002L17.2681 11.9999M17.2686 12.0002L19.0002 13M15.5361 11L17.2681 11.9999M17.2681 11.9999L15.5359 13");
}

.spvw1m4wo {
  d: path("M22 12C22 15.7712 22 17.6569 20.8284 18.8284C19.6569 20 17.7712 20 14 20H10C6.22876 20 4.34315 20 3.17157 18.8284C2 17.6569 2 15.7712 2 12C2 8.22876 2 6.34315 3.17157 5.17157C4.34315 4 6.22876 4 10 4H14C17.7712 4 19.6569 4 20.8284 5.17157C21.4816 5.82475 21.7706 6.69989 21.8985 8");
}

.ucmhfwbcn {
  d: path("M6.73266 10V11.9997M6.73266 11.9997V12.0002M6.73266 11.9997L8.4641 11M6.73266 11.9997L6.73217 11.9999M6.73266 12.0002V14M6.73266 12.0002L6.73217 11.9999M6.73266 12.0002L8.46434 13M5.00023 11L6.73217 11.9999M6.73217 11.9999L5 13");
}

</style>
