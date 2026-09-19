<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="cb0slsbcx"/><path class="doh6vyceq"/><path class="c6oow2bug"/></g><g class="y9tr6bcfx"><path class="dm34lvb0c"/><path class="wg9kd-bxz"/><path class="hiiec-t-x"/><path class="wg-qsgbux"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mods-addons-for-minecraft-pe" /></template>
<style>
.c6oow2bug {
  d: path("M43.17 37.747a6.753 6.753 0 1 1-13.505 0a6.753 6.753 0 0 1 13.505 0");
}

.cb0slsbcx {
  d: path("M37.615 42.295s-.4-.834-1.198-.834s-1.198.834-1.198.834l-1.177-.487s.313-.871-.25-1.435s-1.438-.257-1.438-.257l-.488-1.177s.837-.395.837-1.192s-.834-1.198-.834-1.198l.488-1.177s.87.313 1.434-.251s.251-1.434.251-1.434l1.177-.488s.401.834 1.198.834s1.198-.834 1.198-.834l1.178.488s-.313.87.25 1.434c.565.564 1.438.257 1.438.257l.487 1.177s-.837.395-.837 1.192s.835 1.198.835 1.198l-.488 1.177s-.87-.312-1.434.251c-.564.564-.251 1.435-.251 1.435z");
}

.dm34lvb0c {
  d: path("m4.83 13.661l17.6 10.161v20.196L4.83 33.857z");
}

.doh6vyceq {
  d: path("M38.235 37.747a1.818 1.818 0 1 1-3.635 0a1.818 1.818 0 0 1 3.635 0");
}

.hiiec-t-x {
  d: path("m22.43 3.5l17.599 10.161l-17.6 10.161l-17.6-10.16zm7.517 36.177l-7.518 4.34V23.823h0l17.6-10.16v18.382");
}

.wg-qsgbux {
  d: path("m24.63 32.65l2.2-1.27v-5.05l2.199-1.27v-2.524l2.2-1.27v5.05l2.2-1.271v-2.524l2.2-1.27v2.524l2.2-1.27V19.98l2.2-1.27v-5.048l-2.2 1.27l-2.2 1.27l-2.2 1.27l-2.2 1.27l-2.2 1.27l-2.2 1.27l-2.2 1.27l-2.2 1.27v7.574l2.2-1.27z");
}

.wg9kd-bxz {
  d: path("m7.03 25.029l2.2 1.27V21.25l2.2 1.27v-2.524l2.2 1.27v5.049l2.2 1.27v-2.524l2.2 1.27v2.524l2.2 1.27v-2.524l2.2 1.27v-5.049l-2.2-1.27l-2.2-1.27l-2.2-1.27l-2.2-1.27l-2.2-1.27l-2.2-1.27l-2.2-1.27l-2.2-1.27v7.573l2.2 1.27z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
