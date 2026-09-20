<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG3z7UNe4m)" clip-rule="evenodd" class="i-eeqzf5t"/><path clip-rule="evenodd" class="da3qvnbym"/><defs><linearGradient id="SVG3z7UNe4m" x1="9.111" x2="14.823" y1="3.53" y2="20.494" gradientUnits="userSpaceOnUse"><stop class="f_xxmmhtp"/><stop offset=".044" class="e364r6b1f"/><stop offset=".118" class="fgz813b_b"/><stop offset=".216" class="d57466_cm"/><stop offset=".296" class="zri6_ybmj"/><stop offset=".375" class="w8qs_zbbn"/><stop offset=".468" class="q24_z7bmd"/><stop offset=".58" class="yfzgopbwm"/><stop offset=".709" class="ayuwdmbkc"/><stop offset=".823" class="jbv30jb5a"/><stop offset="1" class="o8mdk3m5a"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:sushiswap" /></template>
<style>
.ayuwdmbkc {
  stop-color: var(--svg-color--f156a3, #f156a3);
}

.d57466_cm {
  stop-color: var(--svg-color--a279bd, #a279bd);
}

.da3qvnbym {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M20.063 11.776c-.674-1.533-2.25-3.337-4.398-4.86c-2.14-1.525-4.364-2.43-6.043-2.566c-1.023-.085-1.832.101-2.241.669l-.017.033c-.384.568-.299 1.372.102 2.287c.673 1.54 2.25 3.344 4.39 4.868c2.138 1.525 4.363 2.43 6.042 2.566c1.005.076 1.798-.101 2.216-.635l.025-.042c.41-.56.324-1.389-.076-2.32m-3.145.034c-.188.262-.571.338-1.04.296c-.844-.068-1.952-.525-3.026-1.287s-1.866-1.66-2.199-2.43c-.187-.432-.238-.813-.05-1.076c.187-.262.57-.339 1.047-.305c.836.077 1.952.525 3.018 1.288c1.074.762 1.866 1.668 2.198 2.438c.197.432.248.813.052 1.076");
}

.e364r6b1f {
  stop-color: var(--svg-color--49a1db, #49a1db);
}

.f_xxmmhtp {
  stop-color: var(--svg-color--27b0e6, #27b0e6);
}

.fgz813b_b {
  stop-color: var(--svg-color--7d8aca, #7d8aca);
}

.ft5dv1b6b {
  fill: none;
}

.i-eeqzf5t {
  fill-rule: evenodd;
  d: path("m20.625 14.451l-3.511 4.878c-.512.71-1.509 1.024-2.779.923c-1.764-.153-4.108-1.084-6.35-2.684a18 18 0 0 1-2.065-1.705c-1.188-1.146-2.06-2.338-2.528-3.402c-.511-1.168-.528-2.201-.017-2.912l3.52-4.878c.511-.71 1.5-1.024 2.778-.923c1.765.144 4.1 1.084 6.35 2.676c2.241 1.6 3.886 3.506 4.585 5.115q.09.207.16.408c.348 1 .308 1.877-.143 2.504");
}

.jbv30jb5a {
  stop-color: var(--svg-color--f853a1, #f853a1);
}

.o8mdk3m5a {
  stop-color: var(--svg-color--fa52a0, #fa52a0);
}

.q24_z7bmd {
  stop-color: var(--svg-color--d563ad, #d563ad);
}

.w8qs_zbbn {
  stop-color: var(--svg-color--c26bb3, #c26bb3);
}

.yfzgopbwm {
  stop-color: var(--svg-color--e65ba7, #e65ba7);
}

.zri6_ybmj {
  stop-color: var(--svg-color--ba6fb6, #ba6fb6);
}

</style>
